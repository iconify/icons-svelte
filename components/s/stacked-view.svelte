<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anvx5lpie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anvx5lpie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stacked-view" {...props}></Icon>
