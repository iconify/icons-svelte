<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ukajbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-ukajbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-edit-outline" {...props}></Icon>
