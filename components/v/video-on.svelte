<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keijgb3kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="keijgb3kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:video-on" {...props}></Icon>
