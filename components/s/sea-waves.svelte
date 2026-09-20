<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vplra2zco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vplra2zco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sea-waves" {...props}></Icon>
