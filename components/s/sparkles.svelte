<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umgqinbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="umgqinbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:sparkles" {...props}></Icon>
