<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z09zfn_om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z09zfn_om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:shield" {...props}></Icon>
