<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5syj6ckj.css';
import '../../css/t/t5lhdhbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5syj6ckj"/><path class="t5lhdhbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:soul" {...props}></Icon>
