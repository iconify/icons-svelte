<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmt_occ7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":548,"height":762};
const content = `<path class="tmt_occ7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:v-upper-case" {...props}></Icon>
