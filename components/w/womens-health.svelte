<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amcb6ybaq.css';
import '../../css/k/kasw7ebxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="amcb6ybaq"/><path class="kasw7ebxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:womens-health" {...props}></Icon>
