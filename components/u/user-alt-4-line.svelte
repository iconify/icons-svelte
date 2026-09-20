<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjjo3sblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjjo3sblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-alt-4-line" {...props}></Icon>
