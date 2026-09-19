<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6dafjbul.css';
import '../../css/w/wrevi32si.css';
import '../../css/b/btx35_8hm.css';
import '../../css/a/ah1zjobhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6dafjbul"/><circle class="wrevi32si"/><path class="btx35_8hm"/><path class="ah1zjobhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:volume-binding" {...props}></Icon>
