<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqbs8rbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqbs8rbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:usd-coin-usdc-line" {...props}></Icon>
