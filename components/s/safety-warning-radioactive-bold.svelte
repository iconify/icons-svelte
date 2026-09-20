<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbqi1ub-j.css';
import '../../css/b/bfj6lrbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbqi1ub-j"/><path class="bfj6lrbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:safety-warning-radioactive-bold" {...props}></Icon>
