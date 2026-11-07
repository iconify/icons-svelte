<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/istl8mb1s.css';
import '../../css/o/oid5rccnd.css';
import '../../css/b/b3f_00ucw.css';
import '../../css/g/g4wbobeno.css';
import '../../css/q/qpw9ik4cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="istl8mb1s"/><path class="oid5rccnd"/><path clip-rule="evenodd" class="b3f_00ucw"/><path class="g4wbobeno"/><path clip-rule="evenodd" class="qpw9ik4cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-money-outline" {...props}></Icon>
