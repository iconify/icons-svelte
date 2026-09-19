<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozoj0vbaf.css';
import '../../css/k/khkqlacip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozoj0vbaf"/><path class="khkqlacip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:swimming-filled" {...props}></Icon>
