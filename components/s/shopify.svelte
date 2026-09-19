<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/oeookeb1a.css';
import '../../css/t/tx58sukui.css';
import '../../css/b/b1io35pet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oeookeb1a"/><path class="tx58sukui"/><path class="b1io35pet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shopify" {...props}></Icon>
