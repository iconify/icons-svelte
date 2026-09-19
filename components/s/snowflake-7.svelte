<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lalqpdp_l.css';
import '../../css/f/f8sr_ibol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="lalqpdp_l"/><path class="f8sr_ibol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake-7" {...props}></Icon>
