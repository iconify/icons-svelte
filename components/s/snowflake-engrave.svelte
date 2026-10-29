<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s72dbeb2y.css';
import '../../css/x/x2zbdkeaw.css';
import '../../css/h/hlsp4ac3y.css';
import '../../css/f/fboa2bbqg.css';
import '../../css/m/mspcjjimr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s72dbeb2y wm-k"/><path class="wm-a x2zbdkeaw"/><path class="hlsp4ac3y wm-shadow"/><path class="fboa2bbqg wm-k"/><path class="mspcjjimr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:snowflake-engrave" {...props}></Icon>
