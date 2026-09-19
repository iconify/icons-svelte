<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpn-pbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wcpn-pbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sale-alt" {...props}></Icon>
