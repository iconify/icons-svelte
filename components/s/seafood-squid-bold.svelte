<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bym9qzlxy.css';
import '../../css/y/yzb5i2o5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bym9qzlxy"/><path class="yzb5i2o5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:seafood-squid-bold" {...props}></Icon>
