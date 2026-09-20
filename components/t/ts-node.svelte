<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcgv1r9pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcgv1r9pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ts-node" {...props}></Icon>
