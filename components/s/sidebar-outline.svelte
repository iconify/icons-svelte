<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5fqjbjy.css';
import '../../css/o/o4ra4ubat.css';
import '../../css/m/mjz7_5-6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl5fqjbjy"/><path class="o4ra4ubat"/><path clip-rule="evenodd" class="mjz7_5-6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sidebar-outline" {...props}></Icon>
