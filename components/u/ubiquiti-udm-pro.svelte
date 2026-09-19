<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oio-htbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oio-htbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-udm-pro" {...props}></Icon>
