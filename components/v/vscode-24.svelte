<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvvy4hbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qvvy4hbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:vscode-24" {...props}></Icon>
