<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldb9tvbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldb9tvbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:sign-direction" {...props}></Icon>
