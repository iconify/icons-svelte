<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhpwx4gkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhpwx4gkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:structure-filled" {...props}></Icon>
