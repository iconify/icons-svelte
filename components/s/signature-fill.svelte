<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swztx7bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swztx7bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signature-fill" {...props}></Icon>
