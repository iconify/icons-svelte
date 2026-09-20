<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8e86bczb.css';
import '../../css/l/lbjnpubsy.css';
import '../../css/y/yl21lvbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8e86bczb"/><path class="lbjnpubsy"/><path class="yl21lvbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-basket" {...props}></Icon>
