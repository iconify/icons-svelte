<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwghczbgl.css';
import '../../css/u/uh-uk-b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwghczbgl"/><path class="uh-uk-b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trip" {...props}></Icon>
