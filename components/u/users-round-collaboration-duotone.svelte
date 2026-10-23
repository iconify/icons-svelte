<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c05_9vbhx.css';
import '../../css/g/gi5g7lm5g.css';
import '../../css/h/hl7ikcc0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c05_9vbhx"/><path class="gi5g7lm5g"/><path class="hl7ikcc0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:users-round-collaboration-duotone" {...props}></Icon>
