<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfh-7gbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfh-7gbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-eye-fill" {...props}></Icon>
