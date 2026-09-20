<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbtv_rbic.css';
import '../../css/e/ea8if3c8i.css';
import '../../css/m/mgzrqm6_d.css';
import '../../css/k/kat0eym1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbtv_rbic"/><path class="ea8if3c8i"/><path class="mgzrqm6_d"/><path class="kat0eym1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:ruler-combined" {...props}></Icon>
