<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gusc8fh9m.css';
import '../../css/p/pzzrm0a9w.css';
import '../../css/r/rvi4blbjl.css';
import '../../css/i/inwbjmbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gusc8fh9m"/><path class="pzzrm0a9w"/><path class="rvi4blbjl"/><path class="inwbjmbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:wallet-twotone" {...props}></Icon>
