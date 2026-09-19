<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmlk_2cbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmlk_2cbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:slash-solid" {...props}></Icon>
