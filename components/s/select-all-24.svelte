<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgp3--bdz.css';
import '../../css/v/v_mxp4bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgp3--bdz"/><path clip-rule="evenodd" class="v_mxp4bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:select-all-24" {...props}></Icon>
