<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntgros_9i.css';
import '../../css/x/xvmpc_kfa.css';
import '../../css/i/iyd3g3q8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntgros_9i"/><path clip-rule="evenodd" class="xvmpc_kfa"/><path clip-rule="evenodd" class="iyd3g3q8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:totem-outline" {...props}></Icon>
