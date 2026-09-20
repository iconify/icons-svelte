<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmzecqb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmzecqb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:woocommerce-logo-solid" {...props}></Icon>
