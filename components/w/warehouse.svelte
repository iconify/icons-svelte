<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shzi5lk7v.css';
import '../../css/z/zkinl8z7h.css';
import '../../css/p/pphg3627g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shzi5lk7v wm-k"/><path class="wm-a zkinl8z7h"/><path class="pphg3627g wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:warehouse" {...props}></Icon>
