<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ews_agbzg.css';
import '../../css/q/q869ue7ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ews_agbzg"/><path clip-rule="evenodd" class="q869ue7ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:stethoscope-outline" {...props}></Icon>
