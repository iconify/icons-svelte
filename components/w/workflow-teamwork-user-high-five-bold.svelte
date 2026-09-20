<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u424brbrp.css';
import '../../css/b/bdi3fdcsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u424brbrp"/><path class="bdi3fdcsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:workflow-teamwork-user-high-five-bold" {...props}></Icon>
