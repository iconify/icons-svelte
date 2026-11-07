<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii1sy95ok.css';
import '../../css/n/npymy_hkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1sy95ok"/><path class="npymy_hkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-academic-cap-bold-duotone" {...props}></Icon>
