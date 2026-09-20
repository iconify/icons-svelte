<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7m_drb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7m_drb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shipment-upload-information-bold" {...props}></Icon>
