<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-rx0gbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-rx0gbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:server-pbx" {...props}></Icon>
