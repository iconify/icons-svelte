<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyrz-1ftw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyrz-1ftw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-right" {...props}></Icon>
