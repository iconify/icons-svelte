<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecm__i54a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecm__i54a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:upgrade" {...props}></Icon>
