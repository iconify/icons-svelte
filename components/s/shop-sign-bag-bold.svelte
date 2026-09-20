<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzs4ogjnt.css';
import '../../css/n/n_w_i9mtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzs4ogjnt"/><path class="n_w_i9mtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shop-sign-bag-bold" {...props}></Icon>
