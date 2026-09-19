<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti0_56jad.css';
import '../../css/c/c34z_sbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti0_56jad"/><path class="c34z_sbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:stack-overflow-fill" {...props}></Icon>
