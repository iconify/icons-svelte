<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lam4d3b4j.css';
import '../../css/y/yrmzb_btc.css';
import '../../css/d/dftf9rvck.css';
import '../../css/p/pxomb-k8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lam4d3b4j"/><path clip-rule="evenodd" class="yrmzb_btc"/><circle class="dftf9rvck"/><path class="pxomb-k8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:safe-filled" {...props}></Icon>
