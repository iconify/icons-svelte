<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf-8gmbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf-8gmbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:step-forward" {...props}></Icon>
