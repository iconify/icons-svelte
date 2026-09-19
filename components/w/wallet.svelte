<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khlp6_3uj.css';
import '../../css/j/jr0jy1wli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khlp6_3uj"/><circle class="jr0jy1wli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:wallet" {...props}></Icon>
