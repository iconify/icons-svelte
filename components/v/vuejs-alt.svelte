<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze6v68axo.css';
import '../../css/r/rii9k4bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze6v68axo"/><path class="rii9k4bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:vuejs-alt" {...props}></Icon>
