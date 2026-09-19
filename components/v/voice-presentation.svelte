<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bng3m8b7n.css';
import '../../css/y/yy-od7caa.css';
import '../../css/o/om051pb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bng3m8b7n"/><circle class="yy-od7caa"/><path class="om051pb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:voice-presentation" {...props}></Icon>
