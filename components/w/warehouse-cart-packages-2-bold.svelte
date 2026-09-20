<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbma2iban.css';
import '../../css/f/fv36o8gan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbma2iban"/><path class="fv36o8gan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:warehouse-cart-packages-2-bold" {...props}></Icon>
