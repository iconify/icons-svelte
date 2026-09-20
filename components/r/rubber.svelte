<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb2so-xcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-2.5};
const content = `<path class="wb2so-xcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:rubber" {...props}></Icon>
