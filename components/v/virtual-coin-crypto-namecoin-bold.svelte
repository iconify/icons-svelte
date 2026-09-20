<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7poolbui.css';
import '../../css/q/qc9ri3n6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7poolbui"/><path class="qc9ri3n6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:virtual-coin-crypto-namecoin-bold" {...props}></Icon>
