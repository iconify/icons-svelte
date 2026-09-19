<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyw-o0bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hyw-o0bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:text-outdent" {...props}></Icon>
