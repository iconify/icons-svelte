<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zffwe4bkl.css';
import '../../css/e/eiv7nvb5h.css';
import '../../css/x/xcoirhi_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zffwe4bkl"/><path class="eiv7nvb5h"/><path class="xcoirhi_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:server" {...props}></Icon>
