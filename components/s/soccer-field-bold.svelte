<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srtsafpvb.css';
import '../../css/t/tzjolqugh.css';
import '../../css/h/hmefgwsmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srtsafpvb"/><path class="tzjolqugh"/><path class="hmefgwsmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:soccer-field-bold" {...props}></Icon>
