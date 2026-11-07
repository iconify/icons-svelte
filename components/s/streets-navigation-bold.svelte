<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa4c_mbug.css';
import '../../css/j/juwk50edv.css';
import '../../css/p/p6myf1z6f.css';
import '../../css/x/xt-xue_6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa4c_mbug"/><path class="juwk50edv"/><path class="p6myf1z6f"/><path class="xt-xue_6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-navigation-bold" {...props}></Icon>
