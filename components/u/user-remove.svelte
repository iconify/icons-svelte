<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq8ypobzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq8ypobzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:user-remove" {...props}></Icon>
