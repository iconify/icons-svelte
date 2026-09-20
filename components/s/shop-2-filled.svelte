<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kis6e-brh.css';
import '../../css/v/vefb5s21n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kis6e-brh"/><path class="vefb5s21n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shop-2-filled" {...props}></Icon>
