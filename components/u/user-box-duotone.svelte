<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjiz8hbrl.css';
import '../../css/h/hana-fm8g.css';
import '../../css/w/w6h6ugqaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjiz8hbrl"/><circle class="hana-fm8g"/><path clip-rule="evenodd" class="w6h6ugqaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-box-duotone" {...props}></Icon>
