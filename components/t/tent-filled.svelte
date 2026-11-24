<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfn12dn-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yfn12dn-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tent-filled" {...props}></Icon>
