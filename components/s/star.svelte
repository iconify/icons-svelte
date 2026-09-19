<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_6ob4nca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_6ob4nca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:star" {...props}></Icon>
