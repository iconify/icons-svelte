<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzyem1bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzyem1bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-police-fill" {...props}></Icon>
