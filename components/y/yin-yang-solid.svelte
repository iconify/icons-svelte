<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx4gduomu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx4gduomu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:yin-yang-solid" {...props}></Icon>
