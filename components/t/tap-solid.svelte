<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peeffdmla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peeffdmla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tap-solid" {...props}></Icon>
