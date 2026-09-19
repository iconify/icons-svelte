<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sje9hqxyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sje9hqxyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shopping-bag-arrow-up" {...props}></Icon>
