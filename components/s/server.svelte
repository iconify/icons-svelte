<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp84ttcgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wp84ttcgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:server" {...props}></Icon>
