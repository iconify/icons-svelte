<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikcde1jrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikcde1jrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sei" {...props}></Icon>
