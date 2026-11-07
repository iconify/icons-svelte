<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp2190qyz.css';
import '../../css/x/x-pf1hz3a.css';
import '../../css/j/j020-w2mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp2190qyz"/><path class="x-pf1hz3a"/><path clip-rule="evenodd" class="j020-w2mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-warning-outline" {...props}></Icon>
