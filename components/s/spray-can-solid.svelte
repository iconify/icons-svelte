<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzuua4itw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzuua4itw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spray-can-solid" {...props}></Icon>
