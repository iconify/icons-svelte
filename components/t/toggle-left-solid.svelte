<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pssw4_ktq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pssw4_ktq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:toggle-left-solid" {...props}></Icon>
