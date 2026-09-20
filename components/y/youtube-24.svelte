<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpwxbbc7k.css';
import '../../css/n/n0w792bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpwxbbc7k"/><path clip-rule="evenodd" class="n0w792bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:youtube-24" {...props}></Icon>
