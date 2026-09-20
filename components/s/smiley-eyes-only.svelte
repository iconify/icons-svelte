<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hurmgkbeh.css';
import '../../css/n/nlg3gqb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hurmgkbeh"/><path class="nlg3gqb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-eyes-only" {...props}></Icon>
