<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b08gyib0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b08gyib0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-x-solid" {...props}></Icon>
