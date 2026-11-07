<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3_8fkw7e.css';
import '../../css/l/llrk-tbrn.css';
import '../../css/n/n6sk80bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3_8fkw7e"/><path class="llrk-tbrn"/><path clip-rule="evenodd" class="n6sk80bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sun-fog-bold" {...props}></Icon>
