<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc9y20byl.css';
import '../../css/p/p4w9xabzc.css';
import '../../css/k/ki0n9xumn.css';
import '../../css/d/d1_f_v9ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc9y20byl"/><path class="p4w9xabzc"/><path class="ki0n9xumn"/><path class="d1_f_v9ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:signal" {...props}></Icon>
