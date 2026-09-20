<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljvi6y.css';
import '../../css/s/s1ui7u.css';
import '../../css/x/xb-a0u.css';
import '../../css/s/so-from-22.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljvi6y s1ui7u"/><path class="s1ui7u xb-a0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:valign-baseline-twotone" {...props}></Icon>
