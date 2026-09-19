<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlo02_iiq.css';
import '../../css/q/qw5e84bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlo02_iiq"/><path class="qw5e84bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:volume-down-outline" {...props}></Icon>
