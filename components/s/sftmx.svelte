<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa_s2gbth.css';
import '../../css/a/amj00lbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa_s2gbth"/><path clip-rule="evenodd" class="amj00lbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sftmx" {...props}></Icon>
