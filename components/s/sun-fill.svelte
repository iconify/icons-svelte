<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zam0b_mmh.css';
import '../../css/i/i1d8z5cie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zam0b_mmh"/><path clip-rule="evenodd" class="i1d8z5cie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:sun-fill" {...props}></Icon>
