<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml6fninwt.css';
import '../../css/w/wlyltdbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ml6fninwt"/><path clip-rule="evenodd" class="wlyltdbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:simohamed-solid" {...props}></Icon>
