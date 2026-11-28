<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snae6cbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snae6cbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sigma" {...props}></Icon>
