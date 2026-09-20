<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuo_d6bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuo_d6bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zhipu" {...props}></Icon>
