<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnnw6covj.css';
import '../../css/r/rjp1fpm9e.css';
import '../../css/s/snp287xku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qnnw6covj"/><path class="rjp1fpm9e"/><path class="snp287xku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:switzerland" {...props}></Icon>
