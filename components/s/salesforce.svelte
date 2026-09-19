<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypa2l2sjm.css';
import '../../css/l/lymew2x1z.css';
import '../../css/o/o8js7wtch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ypa2l2sjm"/><path class="lymew2x1z"/><path class="o8js7wtch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:salesforce" {...props}></Icon>
