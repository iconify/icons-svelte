<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeeel25yq.css';
import '../../css/l/lx933dbek.css';
import '../../css/d/dzzm5i91a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yeeel25yq"/><circle class="lx933dbek"/><path class="dzzm5i91a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:smartphone-outline" {...props}></Icon>
