<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzxq6ibab.css';
import '../../css/q/q_6cgmbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzxq6ibab"/><path class="q_6cgmbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:smartphone-light" {...props}></Icon>
