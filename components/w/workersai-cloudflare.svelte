<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvp5-2bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvp5-2bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:workersai-cloudflare" {...props}></Icon>
