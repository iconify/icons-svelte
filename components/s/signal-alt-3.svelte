<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o98xaoaxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o98xaoaxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:signal-alt-3" {...props}></Icon>
