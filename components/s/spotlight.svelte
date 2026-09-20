<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpcbndban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpcbndban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spotlight" {...props}></Icon>
