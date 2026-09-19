<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr1rmbctj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lr1rmbctj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:sparkles-fill" {...props}></Icon>
