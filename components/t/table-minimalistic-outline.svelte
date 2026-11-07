<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8f365c-u.css';
import '../../css/j/jjp92xbjh.css';
import '../../css/m/mrmmz5sme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8f365c-u"/><path class="jjp92xbjh"/><path class="mrmmz5sme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-minimalistic-outline" {...props}></Icon>
