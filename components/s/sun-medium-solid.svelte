<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m46032bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m46032bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sun-medium-solid" {...props}></Icon>
