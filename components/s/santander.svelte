<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc67xp7dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":90};
const content = `<path class="kc67xp7dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:santander" {...props}></Icon>
