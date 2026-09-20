<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq9_n9cuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq9_n9cuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:star-fill" {...props}></Icon>
