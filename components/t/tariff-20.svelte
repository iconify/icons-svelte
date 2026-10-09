<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2yxnrbti.css';
import '../../css/l/lcxfshbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2yxnrbti"/><path class="lcxfshbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tariff-20" {...props}></Icon>
