<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfla51bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfla51bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:volume-up" {...props}></Icon>
