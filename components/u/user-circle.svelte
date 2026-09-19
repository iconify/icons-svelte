<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usl793bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usl793bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:user-circle" {...props}></Icon>
