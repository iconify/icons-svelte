<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_gh3fqas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_gh3fqas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:star-half-s-fill" {...props}></Icon>
