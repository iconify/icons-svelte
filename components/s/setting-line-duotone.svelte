<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouxp0ubsi.css';
import '../../css/v/v4i2ew1ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ouxp0ubsi"/><circle class="v4i2ew1ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:setting-line-duotone" {...props}></Icon>
