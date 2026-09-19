<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzhtr9y7k.css';
import '../../css/z/zmbgj-x1z.css';
import '../../css/v/vyf6lgyjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lzhtr9y7k"/><path class="zmbgj-x1z"/><path class="vyf6lgyjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:timer" {...props}></Icon>
