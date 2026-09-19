<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye6zn_bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye6zn_bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-lucca-alt-below" {...props}></Icon>
