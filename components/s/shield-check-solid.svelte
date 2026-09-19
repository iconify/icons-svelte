<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs3ol7bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs3ol7bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shield-check-solid" {...props}></Icon>
