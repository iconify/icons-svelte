<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt0hkp.css';
import '../../css/s/s1ui7u.css';
import '../../css/x/xb-a0u.css';
import '../../css/s/so-from-22.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0hkp s1ui7u"/><path class="s1ui7u xb-a0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:valign-middle-twotone" {...props}></Icon>
