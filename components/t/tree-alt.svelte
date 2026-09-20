<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unthb7baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="unthb7baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tree-alt" {...props}></Icon>
