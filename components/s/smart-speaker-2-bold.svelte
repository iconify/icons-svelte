<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijssdnbls.css';
import '../../css/m/m6zv5vbnf.css';
import '../../css/j/jqr1k9a2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijssdnbls"/><path class="m6zv5vbnf"/><path class="jqr1k9a2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-speaker-2-bold" {...props}></Icon>
