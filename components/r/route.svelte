<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv1e92boa.css';
import '../../css/r/rtvgfzeze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv1e92boa"/><path class="rtvgfzeze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:route" {...props}></Icon>
