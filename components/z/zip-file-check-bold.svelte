<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-dnevyfw.css';
import '../../css/m/mw0fk06ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-dnevyfw"/><path class="mw0fk06ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:zip-file-check-bold" {...props}></Icon>
